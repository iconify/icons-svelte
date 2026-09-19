<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w1h-ul-cd.css';
import '../../css/v/v4bz0abgi.css';
import '../../css/g/gxzmdpsnv.css';
import '../../css/h/h3ivwac8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="w1h-ul-cd"/><path clip-rule="evenodd" class="v4bz0abgi"/><path class="gxzmdpsnv"/><path clip-rule="evenodd" class="h3ivwac8i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sd-card-outline" {...props}></Icon>
