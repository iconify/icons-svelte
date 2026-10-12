<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duw3yoprz.css';
import '../../css/p/psd5yeurc.css';
import '../../css/l/l9jgh7bvz.css';
import '../../css/s/st45emjbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="duw3yoprz"/><path class="psd5yeurc"/><path class="l9jgh7bvz"/><path class="st45emjbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tag-plus-48-bold" {...props}></Icon>
