<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq7_6ac2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jq7_6ac2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:stamp" {...props}></Icon>
