<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq8rzkbds.css';
import '../../css/m/mmxhl-bkw.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/h/hlray_uja.css';
import '../../css/t/tzwk1-biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="bq8rzkbds"/><circle class="mmxhl-bkw"/><g class="ij2x_72vy"><path class="hlray_uja"/><circle class="tzwk1-biw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:save" {...props}></Icon>
