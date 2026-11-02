<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sysq-shls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sysq-shls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:version-fill" {...props}></Icon>
