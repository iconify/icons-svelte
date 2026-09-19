<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2yiggbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s2yiggbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:type-hierarchy-super" {...props}></Icon>
