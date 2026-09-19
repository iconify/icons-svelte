<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bybmr1b4l.css';
import '../../css/z/zweu-dnef.css';
import '../../css/j/jt7vshb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="bybmr1b4l"/><path class="zweu-dnef"/><path class="jt7vshb3p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:siren" {...props}></Icon>
