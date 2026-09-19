<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3sqil9-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s3sqil9-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:waterfalls-h" {...props}></Icon>
