<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdgsixb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xdgsixb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:simohamed-outline" {...props}></Icon>
