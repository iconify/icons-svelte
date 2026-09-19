<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/d/dujczsbku.css';
import '../../css/w/w4csg3qim.css';
import '../../css/k/keux18blx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="dujczsbku"/><path class="w4csg3qim"/><path class="keux18blx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:transition-bottom" {...props}></Icon>
