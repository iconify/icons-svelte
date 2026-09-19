<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt_ca-b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lt_ca-b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:text-style" {...props}></Icon>
