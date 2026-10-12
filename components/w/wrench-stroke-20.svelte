<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkfru2t8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hkfru2t8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wrench-stroke-20" {...props}></Icon>
