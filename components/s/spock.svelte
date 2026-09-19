<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcl50ybdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":769,"height":1025};
const content = `<path class="dcl50ybdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:spock" {...props}></Icon>
