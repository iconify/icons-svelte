<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/cx9tddlgw.css';
import '../../css/m/mika2zbzn.css';
import '../../css/v/vclaqt84l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="cx9tddlgw"/><path class="mika2zbzn wm-a"/><path class="vclaqt84l wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:spell-check" {...props}></Icon>
