<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbrhbwb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bbrhbwb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:topbuzz" {...props}></Icon>
