<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nrtkqwbrh.css';
import '../../css/o/oc9g2266h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nrtkqwbrh"/><path class="oc9g2266h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:unlock-muted-duotone" {...props}></Icon>
