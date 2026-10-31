<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_wiu9bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_wiu9bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:snail-round" {...props}></Icon>
