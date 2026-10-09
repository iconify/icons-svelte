<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5-sh3vvp.css';
import '../../css/j/joigvlfvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z5-sh3vvp"/><path class="joigvlfvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:uranium-48" {...props}></Icon>
