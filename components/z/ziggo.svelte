<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3rdxxb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3rdxxb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ziggo" {...props}></Icon>
