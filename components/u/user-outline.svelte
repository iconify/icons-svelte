<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bluf63ski.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bluf63ski"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:user-outline" {...props}></Icon>
