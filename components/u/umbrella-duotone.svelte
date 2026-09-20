<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sphu1debh.css';
import '../../css/p/p5fjdeb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sphu1debh"/><path class="p5fjdeb2j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:umbrella-duotone" {...props}></Icon>
