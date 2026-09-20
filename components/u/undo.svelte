<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfc6mf-ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nfc6mf-ng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:undo" {...props}></Icon>
