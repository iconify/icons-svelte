<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f21hec9sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f21hec9sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:windows-solid" {...props}></Icon>
