<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xbw2qqb1c.css';
import '../../css/f/f1fr8e5tb.css';
import '../../css/h/hu_mhy3vt.css';
import '../../css/a/abcxsmbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xbw2qqb1c"/><path class="f1fr8e5tb"/><path class="hu_mhy3vt"/><path class="abcxsmbgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:wireless-wifi-signal-antenna" {...props}></Icon>
