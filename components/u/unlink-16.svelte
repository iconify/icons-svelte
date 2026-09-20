<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sko34mb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sko34mb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:unlink-16" {...props}></Icon>
