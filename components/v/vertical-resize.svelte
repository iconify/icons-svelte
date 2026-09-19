<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/q-88mvxik.css';
import '../../css/v/vjocsrbku.css';
import '../../css/f/fdap0sbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="q-88mvxik"/><path class="vjocsrbku"/><path class="fdap0sbww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:vertical-resize" {...props}></Icon>
