<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bghxr8bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bghxr8bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:test-tube" {...props}></Icon>
