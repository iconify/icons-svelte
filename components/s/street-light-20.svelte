<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg4jgbz7f.css';
import '../../css/b/bfg6oocam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lg4jgbz7f"/><path class="bfg6oocam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:street-light-20" {...props}></Icon>
