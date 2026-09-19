<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nboed-byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nboed-byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:twitter" {...props}></Icon>
