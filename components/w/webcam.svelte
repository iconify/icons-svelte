<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cm-utbc2b.css';
import '../../css/p/p3ii9wawv.css';
import '../../css/l/lq59qabbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cm-utbc2b"/><path class="p3ii9wawv"/><path class="lq59qabbd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:webcam" {...props}></Icon>
