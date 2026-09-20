<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_n3habvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y_n3habvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:server-16" {...props}></Icon>
