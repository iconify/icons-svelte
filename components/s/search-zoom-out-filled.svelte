<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d13crfb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d13crfb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search-zoom-out-filled" {...props}></Icon>
