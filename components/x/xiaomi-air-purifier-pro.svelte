<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfewfib-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfewfib-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:xiaomi-air-purifier-pro" {...props}></Icon>
