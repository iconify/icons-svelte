<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/y17g8zbpp.css';
import '../../css/f/fqr8fbbds.css';
import '../../css/k/kji6j-bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="y17g8zbpp"/><path class="fqr8fbbds"/><path class="kji6j-bfs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:workflow" {...props}></Icon>
