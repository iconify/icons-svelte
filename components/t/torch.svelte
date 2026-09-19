<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw8ihx1hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":1024};
const content = `<path class="hw8ihx1hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:torch" {...props}></Icon>
