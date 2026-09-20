<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf-y_r2sd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kf-y_r2sd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:send-down-outline" {...props}></Icon>
