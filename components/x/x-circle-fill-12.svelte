<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c82ie6bdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="c82ie6bdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:x-circle-fill-12" {...props}></Icon>
