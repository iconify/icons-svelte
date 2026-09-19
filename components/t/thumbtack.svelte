<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7uzvvwsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w7uzvvwsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:thumbtack" {...props}></Icon>
