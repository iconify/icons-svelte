<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4v2nxbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="x4v2nxbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:supple" {...props}></Icon>
