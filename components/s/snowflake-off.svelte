<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/f00c5zbbz.css';
import '../../css/c/crhnt4v_q.css';
import '../../css/i/ihebp_r-q.css';
import '../../css/i/i-j6hjxsv.css';
import '../../css/v/vb_snbcxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f00c5zbbz"/><path class="crhnt4v_q"/><path class="ihebp_r-q"/><path class="i-j6hjxsv"/><path class="vb_snbcxu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:snowflake-off" {...props}></Icon>
