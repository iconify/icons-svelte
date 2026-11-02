<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzjix4l-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzjix4l-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-vertical-line" {...props}></Icon>
