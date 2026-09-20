<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th4livb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th4livb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wipro" {...props}></Icon>
