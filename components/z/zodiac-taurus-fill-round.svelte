<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwr2qro4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwr2qro4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-taurus-fill-round" {...props}></Icon>
