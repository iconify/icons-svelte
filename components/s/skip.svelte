<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds7-_hb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ds7-_hb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:skip" {...props}></Icon>
