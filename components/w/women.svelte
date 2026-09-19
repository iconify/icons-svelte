<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2x2-mbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l2x2-mbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:women" {...props}></Icon>
