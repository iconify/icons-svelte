<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/fd7fxu0eo.css';
import '../../css/g/geplcma4c.css';
import '../../css/b/bwm5pk45n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="fd7fxu0eo"/><path class="geplcma4c"/><path class="bwm5pk45n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:study-lamp" {...props}></Icon>
