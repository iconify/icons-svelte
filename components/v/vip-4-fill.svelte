<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2t190b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2t190b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vip-4-fill" {...props}></Icon>
