<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4y-fjblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n4y-fjblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:thumbsup-16" {...props}></Icon>
