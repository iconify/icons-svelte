<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggydu70th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ggydu70th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:terminal-fill" {...props}></Icon>
