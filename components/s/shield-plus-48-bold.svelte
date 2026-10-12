<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-nf9rtsz.css';
import '../../css/h/hwjgqrbah.css';
import '../../css/l/l9jgh7bvz.css';
import '../../css/s/st45emjbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r-nf9rtsz"/><path class="hwjgqrbah"/><path class="l9jgh7bvz"/><path class="st45emjbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-plus-48-bold" {...props}></Icon>
