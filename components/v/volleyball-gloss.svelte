<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twj1lm13k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twj1lm13k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:volleyball-gloss" {...props}></Icon>
