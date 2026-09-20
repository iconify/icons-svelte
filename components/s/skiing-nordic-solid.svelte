<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7fdbq97i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y7fdbq97i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:skiing-nordic-solid" {...props}></Icon>
