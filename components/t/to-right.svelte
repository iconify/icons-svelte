<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-vv1bv3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i-vv1bv3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:to-right" {...props}></Icon>
