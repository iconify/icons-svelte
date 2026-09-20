<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1tvi29qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1tvi29qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search-zoom-in2" {...props}></Icon>
