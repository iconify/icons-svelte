<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b13d50bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b13d50bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:screen-full-16" {...props}></Icon>
