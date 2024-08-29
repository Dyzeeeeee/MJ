<script setup>
import { ref } from 'vue';

const visible = ref(false);
</script>

<template>
    <div class="flex text-xl font-bold pt-4 pb-5 pl-4">
        MENU
    </div>
    <div class="flex gap-2 pb-3 text-sm xl:text-9xl font-bold"
        style="overflow-x: auto; white-space: nowrap; scrollbar-width: none; -ms-overflow-style: none;">
        <Button rounded class="min-w-[5rem] xl:min-w-[5rem]"> All</Button>
        <Button outlined rounded class="min-w-[5rem] xl:min-w-[7rem]" size="small"> Drinks</Button>
        <Button outlined rounded class="min-w-[5rem] xl:min-w-[7rem]" size="small"> Drinks</Button>
        <Button outlined rounded class="min-w-[5rem] xl:min-w-[7rem]" size="small"> Drinks</Button>
        <Button outlined rounded class="min-w-[5rem] xl:min-w-[7rem]" size="small"> Drinks</Button>
    </div>

    <div class="grid grid-cols-12 xl:gap-4 gap-4 mt-5 pb-12 mb-12">
        <div class="col-span-12 lg:col-span-6 xl:col-span-8 -mx7 xl:m-0 gap-2">
            <div class="card p-0 h-auto pb-5 mx-2 mb-4">
                <div class="flex relative ">
                    <div class="text-3xl p-2 absolute bg-red-500 rounded-r-lg  font-bold bottom-3">
                        ₱100
                    </div>
                    <img src="@/assets/pics/SisigRice.jpg"
                        class="object-cover xl:h-[20vh] h-[15vh] w-full rounded-t-lg" />
                </div>
                <div class="flex  pt-2 ml-4 xl:ml-0 xl:pt-0 xl:mt-4">
                    <div class="xl:w-2/12"></div>
                    <div class="xl:w-70 flex-1 flex-wrap">
                        <div class="flex justify-between w-full">
                            <div class="flex flex-col">
                                <div class="text-2xl font-bold xl:text-4xl">Sisig Rice</div>
                                <div class="text-sm italic xl:text-lg">10-15 minutes</div>
                            </div>
                            <div class="self-center px-4">
                                <Button size="small" rounded>
                                    Add to Order
                                </Button>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </div>
        <div class="col-span-12 lg:col-span-6 xl:col-span-8 -mx7 xl:m-0 gap-2">
            <div class="card p-0 h-auto pb-5 mx-2 mb-4">
                <div class="flex relative ">
                    <div class="text-3xl p-2 absolute bg-red-500 rounded-r-lg  font-bold bottom-3">
                        ₱100
                    </div>
                    <img src="@/assets/pics/SisigRice.jpg"
                        class="object-cover xl:h-[20vh] h-[15vh] w-full rounded-t-lg" />
                </div>
                <div class="flex  pt-2 ml-4 xl:ml-0 xl:pt-0 xl:mt-4">
                    <div class="xl:w-2/12"></div>
                    <div class="xl:w-70 flex-1 flex-wrap">
                        <div class="flex justify-between w-full">
                            <div class="flex flex-col">
                                <div class="text-2xl font-bold xl:text-4xl">Sisig Rice</div>
                                <div class="text-sm italic xl:text-lg">10-15 minutes</div>
                            </div>
                            <div class="self-center px-4">
                                <Button size="small" rounded>
                                    Add to Order
                                </Button>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </div>
        <div class="col-span-12 lg:col-span-6 xl:col-span-8 -mx7 xl:m-0 gap-2">
            <div class="card p-0 h-auto pb-5 mx-2 mb-4">
                <div class="flex relative ">
                    <div class="text-3xl p-2 absolute bg-red-500 rounded-r-lg  font-bold bottom-3">
                        ₱100
                    </div>
                    <img src="@/assets/pics/SisigRice.jpg"
                        class="object-cover xl:h-[20vh] h-[15vh] w-full rounded-t-lg" />
                </div>
                <div class="flex  pt-2 ml-4 xl:ml-0 xl:pt-0 xl:mt-4">
                    <div class="xl:w-2/12"></div>
                    <div class="xl:w-70 flex-1 flex-wrap">
                        <div class="flex justify-between w-full">
                            <div class="flex flex-col">
                                <div class="text-2xl font-bold xl:text-4xl">Sisig Rice</div>
                                <div class="text-sm italic xl:text-lg">10-15 minutes</div>
                            </div>
                            <div class="self-center px-4">
                                <Button size="small" rounded>
                                    Add to Order
                                </Button>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="fixed bottom-0 left-1/2 transform -translate-x-1/2 mb-2">
    <Button @click="visible = true" severity="success" style="border-radius: 9999px; width: 13rem; height: 7rem; display: flex; flex-direction: column; justify-content: flex-start; align-items: center; padding-top: 0.5rem;">
        <div class="flex flex-col items-center">
            <div class="flex justify-center">
                <Icon icon="oui:arrow-up" width="20" height="20" />
            </div>
            <div class="flex justify-center mt-1">
                <Icon icon="ic:baseline-shopping-cart" width="20" height="20" />
                <span class="ml-1 font-bold">My orders</span>
            </div>
        </div>
    </Button>
</div>


</template>

<style></style>
