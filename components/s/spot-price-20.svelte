<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnfksvwxf.css';
import '../../css/r/rxuug6rfw.css';
import '../../css/k/kf8qud5kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fnfksvwxf"/><path class="rxuug6rfw"/><path class="kf8qud5kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spot-price-20" {...props}></Icon>
