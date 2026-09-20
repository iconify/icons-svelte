<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agm_q7boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="agm_q7boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:scala-16" {...props}></Icon>
