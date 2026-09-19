<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtl3advap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gtl3advap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:wind" {...props}></Icon>
