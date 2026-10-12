<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2wv7tbdk.css';
import '../../css/f/flbhffbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y2wv7tbdk"/><path class="flbhffbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scanner-20" {...props}></Icon>
