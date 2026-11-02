<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhr38dbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhr38dbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:volume-mute-fill" {...props}></Icon>
