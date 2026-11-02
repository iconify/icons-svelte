<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyapg9piq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyapg9piq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scan-2-line" {...props}></Icon>
