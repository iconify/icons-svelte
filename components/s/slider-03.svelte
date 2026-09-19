<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqa6kvbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqa6kvbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:slider-03" {...props}></Icon>
