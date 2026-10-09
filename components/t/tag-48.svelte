<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrjnvkbuz.css';
import '../../css/n/nl3t421aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lrjnvkbuz"/><path class="nl3t421aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tag-48" {...props}></Icon>
