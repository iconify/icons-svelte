<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngrcr4m5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngrcr4m5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:siri-frame-fill" {...props}></Icon>
