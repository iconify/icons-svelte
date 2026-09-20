<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du2s2hbvi.css';
import '../../css/p/p6bj_kbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="du2s2hbvi"/><path class="p6bj_kbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:shape-pyramid" {...props}></Icon>
