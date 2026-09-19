<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk2g5blwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bk2g5blwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:triangle" {...props}></Icon>
