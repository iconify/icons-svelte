<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f841agbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f841agbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:tiktok-16" {...props}></Icon>
