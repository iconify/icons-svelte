<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yeaf2cblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yeaf2cblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-hotel-serving-dome-cook-tool-dome-kitchen-drink-serving-platter-dish-tools-food-cooking" {...props}></Icon>
