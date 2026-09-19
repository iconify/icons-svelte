<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ani_nmk9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ani_nmk9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:tiktok" {...props}></Icon>
