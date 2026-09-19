<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d51h-vdfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d51h-vdfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:tag-outline" {...props}></Icon>
