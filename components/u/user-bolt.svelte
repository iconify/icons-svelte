<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lykg3ubvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lykg3ubvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:user-bolt" {...props}></Icon>
