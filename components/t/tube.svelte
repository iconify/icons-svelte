<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzao40b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bzao40b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tube" {...props}></Icon>
