<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j23q30xfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j23q30xfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safety-certificate-fill" {...props}></Icon>
