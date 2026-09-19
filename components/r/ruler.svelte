<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njtq08kwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="njtq08kwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:ruler" {...props}></Icon>
