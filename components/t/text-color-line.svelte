<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd5zuubcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd5zuubcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-color-line" {...props}></Icon>
