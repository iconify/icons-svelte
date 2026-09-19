<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujmtbcmfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ujmtbcmfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:source-control" {...props}></Icon>
