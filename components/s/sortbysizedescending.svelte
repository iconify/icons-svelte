<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru2pwbhep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="ru2pwbhep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:sortbysizedescending" {...props}></Icon>
