<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw4g0-bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="qw4g0-bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:surgical-knife" {...props}></Icon>
