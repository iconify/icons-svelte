<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p5-m-nb_s.css';
import '../../css/v/v71dgib_d.css';
import '../../css/v/v0mji9zsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p5-m-nb_s"/><path class="v71dgib_d"/><path class="v0mji9zsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:video-frame-2-line-duotone" {...props}></Icon>
