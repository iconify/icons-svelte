<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/vqydno98w.css';
import '../../css/e/er0tjywys.css';
import '../../css/l/lalau4osm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vqydno98w"/><rect class="er0tjywys"/><path class="lalau4osm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:watch-square" {...props}></Icon>
