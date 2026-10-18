<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2jxlvb2i.css';
import '../../css/t/t-4rqjbfm.css';
import '../../css/k/ke-yukwch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f2jxlvb2i"/><path class="t-4rqjbfm"/><path class="ke-yukwch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scour-protection-48-bold" {...props}></Icon>
