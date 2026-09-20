<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep1i_037m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep1i_037m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:trash7-filled" {...props}></Icon>
