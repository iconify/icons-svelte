<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9x5x4j_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9x5x4j_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tv-time" {...props}></Icon>
