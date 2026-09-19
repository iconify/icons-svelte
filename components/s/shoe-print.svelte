<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/urra7zbtu.css';
import '../../css/w/wcoui61up.css';
import '../../css/e/ei46kjzmg.css';
import '../../css/k/kgsfw5daa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="urra7zbtu"/><path clip-rule="evenodd" class="wcoui61up"/><path class="ei46kjzmg"/><path class="kgsfw5daa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:shoe-print" {...props}></Icon>
