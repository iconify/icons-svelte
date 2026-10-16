<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnk58xbgu.css';
import '../../css/i/ifbfh7xzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rnk58xbgu"/><path class="ifbfh7xzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:waypoints-48-bold" {...props}></Icon>
