<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhi3rlo9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhi3rlo9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:slider-vertical-3-fill-round" {...props}></Icon>
