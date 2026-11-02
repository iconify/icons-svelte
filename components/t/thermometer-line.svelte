<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr67ybbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr67ybbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:thermometer-line" {...props}></Icon>
