<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0nfnpd3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0nfnpd3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:volume-mute-fill" {...props}></Icon>
