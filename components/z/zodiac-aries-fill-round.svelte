<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl10nzj9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rl10nzj9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-aries-fill-round" {...props}></Icon>
