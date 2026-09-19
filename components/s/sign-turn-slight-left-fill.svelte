<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvi0ffils.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bvi0ffils"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sign-turn-slight-left-fill" {...props}></Icon>
