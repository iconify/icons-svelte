<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/o/obk939lcu.css';
import '../../css/u/ui8bbrboc.css';
import '../../css/w/w_sg-8h8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="obk939lcu"/><path clip-rule="evenodd" class="ui8bbrboc"/><path class="w_sg-8h8x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sticky-note-minus-sharp-duotone" {...props}></Icon>
