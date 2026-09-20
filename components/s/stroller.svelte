<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul-5fu98g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ul-5fu98g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:stroller" {...props}></Icon>
