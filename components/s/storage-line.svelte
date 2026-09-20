<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_ez1ac2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_ez1ac2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:storage-line" {...props}></Icon>
