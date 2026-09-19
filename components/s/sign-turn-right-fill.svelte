<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2_u9j41c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f2_u9j41c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sign-turn-right-fill" {...props}></Icon>
