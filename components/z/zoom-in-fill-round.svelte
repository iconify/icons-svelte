<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwub9tb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwub9tb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zoom-in-fill-round" {...props}></Icon>
