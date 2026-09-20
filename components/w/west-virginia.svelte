<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whvnh9-te.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="whvnh9-te"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:west-virginia" {...props}></Icon>
