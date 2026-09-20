<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db9qszbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="db9qszbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:shelf-up-outline" {...props}></Icon>
