<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdtvt3bkl.css';
import '../../css/b/bypdiev1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gdtvt3bkl"/><path class="bypdiev1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sailboat-48-bold" {...props}></Icon>
