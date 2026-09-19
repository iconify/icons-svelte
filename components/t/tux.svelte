<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfyy1timd.css';
import '../../css/p/p7q2zbbrp.css';
import '../../css/s/s9yzznvaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfyy1timd"/><path class="p7q2zbbrp"/><path class="s9yzznvaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:tux" {...props}></Icon>
