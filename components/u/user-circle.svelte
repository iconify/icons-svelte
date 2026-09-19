<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/snm_llb0d.css';
import '../../css/k/k3tk-pelt.css';
import '../../css/v/v3nqtefag.css';
import '../../css/d/dddk1uvez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="snm_llb0d"/><path class="k3tk-pelt"/><path clip-rule="evenodd" class="v3nqtefag"/><path class="dddk1uvez"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:user-circle" {...props}></Icon>
