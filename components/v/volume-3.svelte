<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0bic7b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0bic7b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:volume-3" {...props}></Icon>
