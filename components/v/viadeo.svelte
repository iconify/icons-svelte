<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqjn98bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqjn98bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:viadeo" {...props}></Icon>
