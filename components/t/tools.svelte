<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2cv6biat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p2cv6biat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:tools" {...props}></Icon>
