<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpwzu8bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wpwzu8bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sparkle-fill-16" {...props}></Icon>
