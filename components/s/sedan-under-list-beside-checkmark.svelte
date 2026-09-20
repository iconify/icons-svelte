<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeny3cb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aeny3cb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sedan-under-list-beside-checkmark" {...props}></Icon>
