<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixd3b-p8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixd3b-p8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:the-storygraph" {...props}></Icon>
