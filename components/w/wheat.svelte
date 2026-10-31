<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/f/fr2e1qcvy.css';
import '../../css/u/ueo_owbeo.css';
import '../../css/v/vac07x-bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="fr2e1qcvy wm-shadow"/><path class="ueo_owbeo wm-shadow"/><path class="vac07x-bt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:wheat" {...props}></Icon>
