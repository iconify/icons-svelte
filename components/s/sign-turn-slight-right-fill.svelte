<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5-h9ibar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i5-h9ibar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sign-turn-slight-right-fill" {...props}></Icon>
