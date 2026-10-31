<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/o/o4bjcmbul.css';
import '../../css/z/zlg_u3b_t.css';
import '../../css/d/dc82hfbss.css';
import '../../css/i/ie3ykpgds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="o4bjcmbul wm-shadow"/><path class="wm-shadow zlg_u3b_t"/><path class="dc82hfbss"/><path class="ie3ykpgds"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:send-horizontal" {...props}></Icon>
