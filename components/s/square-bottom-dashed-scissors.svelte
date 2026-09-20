<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/limkoio6o.css';
import '../../css/d/d2umvjsxg.css';
import '../../css/y/yopadjb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="limkoio6o"/><circle class="d2umvjsxg"/><circle class="yopadjb1x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:square-bottom-dashed-scissors" {...props}></Icon>
