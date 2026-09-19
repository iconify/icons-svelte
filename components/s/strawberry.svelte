<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esom1xbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":961};
const content = `<path class="esom1xbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:strawberry" {...props}></Icon>
