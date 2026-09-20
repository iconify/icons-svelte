<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz0tcpzbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz0tcpzbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:voelkner" {...props}></Icon>
