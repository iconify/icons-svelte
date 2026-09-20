<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f91v1qb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f91v1qb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:typography-16" {...props}></Icon>
