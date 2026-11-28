<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/og9sisiac.css';
import '../../css/f/f9bybebcd.css';
import '../../css/d/dsgdte86s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="og9sisiac"/><path class="f9bybebcd"/><path class="dsgdte86s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:variable-duo" {...props}></Icon>
