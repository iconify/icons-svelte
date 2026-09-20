<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onhc3xo-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="onhc3xo-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:user-add" {...props}></Icon>
