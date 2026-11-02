<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njzu_tb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njzu_tb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:video-camera-line" {...props}></Icon>
