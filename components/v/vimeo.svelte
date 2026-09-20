<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_wgvebfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-3.5};
const content = `<path class="g_wgvebfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:vimeo" {...props}></Icon>
