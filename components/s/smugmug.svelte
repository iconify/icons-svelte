<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw8i7gzgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw8i7gzgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:smugmug" {...props}></Icon>
