<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/ij3vyybgh.css';
import '../../css/w/w3i1zx0jw.css';
import '../../css/t/toteg6s6e.css';
import '../../css/r/rt7fb-bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ij3vyybgh"/><path class="w3i1zx0jw"/><path class="toteg6s6e"/><path class="rt7fb-bar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:van" {...props}></Icon>
