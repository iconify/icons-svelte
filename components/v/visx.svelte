<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blz_a82jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blz_a82jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:visx" {...props}></Icon>
