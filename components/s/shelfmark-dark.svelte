<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyvj2gbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eyvj2gbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shelfmark-dark" {...props}></Icon>
