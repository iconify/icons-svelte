<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhe0cabnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hhe0cabnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:sd" {...props}></Icon>
