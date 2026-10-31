<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtyiyvblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtyiyvblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:square-minus-gloss" {...props}></Icon>
