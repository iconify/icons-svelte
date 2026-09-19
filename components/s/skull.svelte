<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnue5lbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnue5lbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:skull" {...props}></Icon>
