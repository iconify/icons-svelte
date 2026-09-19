<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_q4cib9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_q4cib9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tv-filled" {...props}></Icon>
