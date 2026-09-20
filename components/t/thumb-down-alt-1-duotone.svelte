<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/foe-smumj.css';
import '../../css/r/rt_27bc2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="foe-smumj"/><path class="rt_27bc2t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:thumb-down-alt-1-duotone" {...props}></Icon>
