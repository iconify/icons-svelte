<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov4c9mb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ov4c9mb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:scanner" {...props}></Icon>
