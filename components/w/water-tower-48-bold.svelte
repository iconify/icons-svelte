<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j63hg3b3u.css';
import '../../css/j/je8d7-b9z.css';
import '../../css/e/e9n3d1ijm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j63hg3b3u"/><path class="je8d7-b9z"/><path class="e9n3d1ijm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:water-tower-48-bold" {...props}></Icon>
