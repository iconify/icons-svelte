<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/a7kvwmrgj.css';
import '../../css/b/bmr1n2fhi.css';
import '../../css/d/d1qde5res.css';
import '../../css/a/ai5b7_bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="a7kvwmrgj"/><path class="bmr1n2fhi"/><path class="d1qde5res"/><path class="ai5b7_bas"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:video-player-movie" {...props}></Icon>
