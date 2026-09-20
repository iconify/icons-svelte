<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n39kd-lul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n39kd-lul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:traffic-cone-line" {...props}></Icon>
