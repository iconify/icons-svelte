<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4gjp9e0a.css';
import '../../css/x/xho5iubuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u4gjp9e0a"/><path class="xho5iubuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-x-20" {...props}></Icon>
