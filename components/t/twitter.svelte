<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic-ap717q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ic-ap717q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:twitter" {...props}></Icon>
