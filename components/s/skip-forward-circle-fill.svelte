<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fusgogbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fusgogbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:skip-forward-circle-fill" {...props}></Icon>
