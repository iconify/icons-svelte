<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pf1tdnshj.css';
import '../../css/o/onn26uc-u.css';
import '../../css/u/udh2xlitm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pf1tdnshj"/><path clip-rule="evenodd" class="onn26uc-u"/><path class="udh2xlitm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:turntable-music-note-bold-duotone" {...props}></Icon>
