<template>
    <div>
        <DefaultLayoutTopMenuBar />
        <div class="flex flex-row card-container ">
            <div class="flex  flex-none">Sidebar</div>
            <div class="flex-grow-1 flex">
                <slot />
            </div>
        </div>
    </div>
</template>
