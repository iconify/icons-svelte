<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6iikjgcv.css';
import '../../css/g/g2svsm15l.css';
import '../../css/z/z04drlb1l.css';
import '../../css/r/rmgjt6byk.css';
import '../../css/j/jii6c3x9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="s6iikjgcv"/><path class="g2svsm15l"/><g class="z04drlb1l"><path class="rmgjt6byk"/><path class="jii6c3x9u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:smiling-face-with-hearts" {...props}></Icon>
