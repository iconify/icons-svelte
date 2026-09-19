<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpb40ebmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xpb40ebmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sign-no-right-turn" {...props}></Icon>
