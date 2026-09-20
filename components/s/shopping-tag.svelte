<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz7nzvb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gz7nzvb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:shopping-tag" {...props}></Icon>
