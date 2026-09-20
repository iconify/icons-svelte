<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy6o-6bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qy6o-6bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uptimekit-dark" {...props}></Icon>
