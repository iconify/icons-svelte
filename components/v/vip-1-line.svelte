<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf9belbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf9belbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vip-1-line" {...props}></Icon>
