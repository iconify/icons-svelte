<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a048g4nwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a048g4nwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:terminal-solid" {...props}></Icon>
