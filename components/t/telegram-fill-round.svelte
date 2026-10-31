<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbu9v-bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbu9v-bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:telegram-fill-round" {...props}></Icon>
