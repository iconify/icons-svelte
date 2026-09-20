<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szgh9cbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="szgh9cbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:smartphone-16" {...props}></Icon>
