<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_2tle25d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_2tle25d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scan-2-fill" {...props}></Icon>
