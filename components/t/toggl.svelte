<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn0pj9vvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jn0pj9vvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:toggl" {...props}></Icon>
