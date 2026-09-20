<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5i1b_2rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5i1b_2rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:spreadsheet" {...props}></Icon>
