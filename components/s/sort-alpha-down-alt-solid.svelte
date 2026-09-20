<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1it6dm-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j1it6dm-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sort-alpha-down-alt-solid" {...props}></Icon>
