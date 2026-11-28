<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp267jbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lp267jbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:scan-face-x" {...props}></Icon>
