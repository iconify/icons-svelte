<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsm-zt1sg.css';
import '../../css/e/eg_g120yy.css';
import '../../css/h/hy4sx7b2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dsm-zt1sg"/><path class="eg_g120yy"/><path class="hy4sx7b2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scissors-48" {...props}></Icon>
