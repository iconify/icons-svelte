<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsdhqux0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsdhqux0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:the-storygraph" {...props}></Icon>
