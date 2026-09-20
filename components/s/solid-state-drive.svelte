<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h52--1z7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="h52--1z7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:solid-state-drive" {...props}></Icon>
