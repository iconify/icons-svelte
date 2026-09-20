<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0bc9uw-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v0bc9uw-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:strikethrough" {...props}></Icon>
