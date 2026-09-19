<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox9ez0b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ox9ez0b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:sun-plant-wilt" {...props}></Icon>
