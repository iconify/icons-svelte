<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axc5g2bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="axc5g2bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:swimmer" {...props}></Icon>
