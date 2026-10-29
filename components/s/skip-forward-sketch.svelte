<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jo_g69brx.css';
import '../../css/q/qyrjxjf9z.css';
import '../../css/a/a9dtoru8r.css';
import '../../css/n/nw6l0ct4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jo_g69brx"/><path class="qyrjxjf9z wm-a"/><path class="a9dtoru8r wm-k"/><path class="nw6l0ct4n wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:skip-forward-sketch" {...props}></Icon>
