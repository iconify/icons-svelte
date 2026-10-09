<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihnl7ab7i.css';
import '../../css/k/k8yin4bou.css';
import '../../css/g/gfbmiabsc.css';
import '../../css/w/wvft85b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ihnl7ab7i"/><path class="k8yin4bou"/><path class="gfbmiabsc"/><path class="wvft85b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-irradiance-48-bold" {...props}></Icon>
