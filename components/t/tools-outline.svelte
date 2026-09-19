<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tecxd3bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tecxd3bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:tools-outline" {...props}></Icon>
