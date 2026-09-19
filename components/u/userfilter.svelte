<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrd_53ogm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="qrd_53ogm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:userfilter" {...props}></Icon>
