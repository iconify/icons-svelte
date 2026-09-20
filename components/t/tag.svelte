<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-bi-qb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="x-bi-qb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:tag" {...props}></Icon>
