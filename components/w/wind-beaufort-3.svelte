<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1nvo3hea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="k1nvo3hea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-beaufort-3" {...props}></Icon>
