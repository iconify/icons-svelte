<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv4wbxftm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pv4wbxftm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:switch-track" {...props}></Icon>
