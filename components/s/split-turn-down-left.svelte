<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/u/u3p9f6bio.css';
import '../../css/j/jcnwc2blw.css';
import '../../css/k/kym7xq7br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="u3p9f6bio"/><circle transform="rotate(-90 37 8.944)" class="jcnwc2blw"/><path class="kym7xq7br"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:split-turn-down-left" {...props}></Icon>
