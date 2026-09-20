<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fpll9nmog.css';
import '../../css/p/pqo6v4bsc.css';
import '../../css/r/r_580nbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fpll9nmog"/><path class="pqo6v4bsc"/><path class="r_580nbkq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate-color:weather-sun" {...props}></Icon>
