<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/a/a3xuudbsq.css';
import '../../css/p/pvov8nfpk.css';
import '../../css/i/i736hpbfw.css';
import '../../css/l/ljigsdbam.css';
import '../../css/u/u3i10hqhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect transform="rotate(90 18 9)" class="a3xuudbsq"/><rect transform="rotate(90 18 17)" class="pvov8nfpk"/><rect transform="rotate(-90 3 7)" class="i736hpbfw"/><path class="ljigsdbam"/><path class="u3i10hqhh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:subttasks-fill" {...props}></Icon>
