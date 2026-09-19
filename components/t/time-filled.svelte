<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frg81opju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frg81opju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:time-filled" {...props}></Icon>
