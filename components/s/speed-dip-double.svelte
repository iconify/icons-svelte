<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kywr7xg6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kywr7xg6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:speed-dip-double" {...props}></Icon>
