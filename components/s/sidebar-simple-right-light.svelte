<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2rct2h3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="g2rct2h3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sidebar-simple-right-light" {...props}></Icon>
