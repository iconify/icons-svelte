<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/z84xh0buz.css';
import '../../css/y/y3ltpce6i.css';
import '../../css/j/j01-b3t0a.css';
import '../../css/l/lz-jyrplx.css';
import '../../css/r/rh61s1a2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="z84xh0buz"/><path class="y3ltpce6i"/><path class="j01-b3t0a"/><path class="lz-jyrplx"/><path class="rh61s1a2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:saving-piggy-bank" {...props}></Icon>
