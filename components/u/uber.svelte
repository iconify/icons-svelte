<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/sgb82cb7q.css';
import '../../css/o/oebz2gi6i.css';
import '../../css/l/lreh8ubkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="sgb82cb7q"/><path class="oebz2gi6i"/><path class="lreh8ubkk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:uber" {...props}></Icon>
