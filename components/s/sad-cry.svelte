<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh3-hqbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gh3-hqbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:sad-cry" {...props}></Icon>
