<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aouu4gbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="aouu4gbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:star" {...props}></Icon>
