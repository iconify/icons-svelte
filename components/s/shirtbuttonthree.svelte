<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt-ujmo2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rt-ujmo2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:shirtbuttonthree" {...props}></Icon>
