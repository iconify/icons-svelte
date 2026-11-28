<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vug2bknhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vug2bknhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:virus-check" {...props}></Icon>
