<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoi7d2btf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hoi7d2btf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:up-fill" {...props}></Icon>
