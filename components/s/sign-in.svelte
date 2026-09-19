<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8h8-kk1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c8h8-kk1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:sign-in" {...props}></Icon>
