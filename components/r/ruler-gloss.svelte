<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w19cm5b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w19cm5b1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ruler-gloss" {...props}></Icon>
