<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc1e_-bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="cc1e_-bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:truck" {...props}></Icon>
