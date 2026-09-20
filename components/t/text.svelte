<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itzhgkb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itzhgkb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:text" {...props}></Icon>
