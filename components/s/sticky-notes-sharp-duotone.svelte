<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/c/c-fn48bus.css';
import '../../css/a/a-22vyg5o.css';
import '../../css/x/xe6tfdcfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="c-fn48bus"/><path class="a-22vyg5o"/><path clip-rule="evenodd" class="xe6tfdcfq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sticky-notes-sharp-duotone" {...props}></Icon>
