<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo9hok72z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oo9hok72z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:shopping-jewels" {...props}></Icon>
