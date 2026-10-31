<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/m/m_1eq48tk.css';
import '../../css/u/uvir12b9m.css';
import '../../css/h/ho994gbvl.css';
import '../../css/k/kb_zc_bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="m_1eq48tk wm-shadow"/><path class="uvir12b9m wm-shadow"/><path class="ho994gbvl"/><path class="kb_zc_bwq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:star-half" {...props}></Icon>
