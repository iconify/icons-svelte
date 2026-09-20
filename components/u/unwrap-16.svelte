<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1kzwfi4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n1kzwfi4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:unwrap-16" {...props}></Icon>
