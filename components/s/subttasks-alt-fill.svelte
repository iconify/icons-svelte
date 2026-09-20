<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/e/edun5zbmv.css';
import '../../css/j/jdpr-jb0b.css';
import '../../css/q/q90b_qbjv.css';
import '../../css/j/j9zbk3bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect transform="rotate(90 16 9)" class="edun5zbmv"/><rect transform="rotate(90 20 17)" class="jdpr-jb0b"/><path class="q90b_qbjv"/><path class="j9zbk3bom"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:subttasks-alt-fill" {...props}></Icon>
