<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avj0nu6ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="avj0nu6ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sidebar-simple-right" {...props}></Icon>
