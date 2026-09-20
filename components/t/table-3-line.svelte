<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex3-_xbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex3-_xbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:table-3-line" {...props}></Icon>
