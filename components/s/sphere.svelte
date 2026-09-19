<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu1_sz9lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cu1_sz9lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:sphere" {...props}></Icon>
