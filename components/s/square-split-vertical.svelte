<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/os8oqcbut.css';
import '../../css/f/fjdvl-bkk.css';
import '../../css/i/ilo04bcis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="os8oqcbut"/><path class="fjdvl-bkk"/><path class="ilo04bcis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-split-vertical" {...props}></Icon>
