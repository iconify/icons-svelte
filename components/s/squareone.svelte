<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs_sp7bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="hs_sp7bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squareone" {...props}></Icon>
