<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guts1yb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="guts1yb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:switch" {...props}></Icon>
