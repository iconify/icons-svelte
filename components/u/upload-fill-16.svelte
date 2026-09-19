<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv25jylpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wv25jylpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:upload-fill-16" {...props}></Icon>
