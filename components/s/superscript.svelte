<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku3qf6bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ku3qf6bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:superscript" {...props}></Icon>
