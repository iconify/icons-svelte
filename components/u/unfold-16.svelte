<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/futdkq_zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="futdkq_zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:unfold-16" {...props}></Icon>
