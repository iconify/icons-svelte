<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7t213qvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k7t213qvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:trophy-16" {...props}></Icon>
