<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joajan00w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="joajan00w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:womans-boot" {...props}></Icon>
