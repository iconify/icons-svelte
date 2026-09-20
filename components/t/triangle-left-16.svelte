<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viikj1bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="viikj1bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:triangle-left-16" {...props}></Icon>
