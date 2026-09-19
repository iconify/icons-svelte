<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avl6-q8xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="avl6-q8xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:volume-mute" {...props}></Icon>
