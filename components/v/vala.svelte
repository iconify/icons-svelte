<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u59a1m3qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u59a1m3qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:vala" {...props}></Icon>
