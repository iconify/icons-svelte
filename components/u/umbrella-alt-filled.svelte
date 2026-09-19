<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlo8iz2zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlo8iz2zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:umbrella-alt-filled" {...props}></Icon>
