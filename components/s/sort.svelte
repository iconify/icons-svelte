<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akjnrbb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="akjnrbb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:sort" {...props}></Icon>
