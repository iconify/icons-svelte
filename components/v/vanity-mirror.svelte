<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aggrzgk7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aggrzgk7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:vanity-mirror" {...props}></Icon>
