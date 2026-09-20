<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/m/muq09cbqz.css';
import '../../css/v/vot250bpi.css';
import '../../css/k/knt4apnld.css';
import '../../css/m/mk8d_nbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="muq09cbqz"/><path class="vot250bpi"/><path class="knt4apnld"/><path class="mk8d_nbic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:server-edit" {...props}></Icon>
