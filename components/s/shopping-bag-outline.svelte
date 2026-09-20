<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj0rd9brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jj0rd9brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:shopping-bag-outline" {...props}></Icon>
