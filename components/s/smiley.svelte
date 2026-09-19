<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4ndl4blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v4ndl4blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:smiley" {...props}></Icon>
