<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxvxe8b2t.css';
import '../../css/q/qybors25i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gxvxe8b2t"/><path class="qybors25i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:toodoom-light" {...props}></Icon>
