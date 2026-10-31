<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r151b58lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r151b58lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wheat-gloss" {...props}></Icon>
