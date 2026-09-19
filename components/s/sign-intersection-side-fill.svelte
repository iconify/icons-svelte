<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_vt4xbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e_vt4xbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sign-intersection-side-fill" {...props}></Icon>
