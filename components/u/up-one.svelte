<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpkju8wre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rpkju8wre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:up-one" {...props}></Icon>
