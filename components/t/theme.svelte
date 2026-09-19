<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx9gfpabu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nx9gfpabu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:theme" {...props}></Icon>
