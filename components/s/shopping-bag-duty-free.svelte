<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq95s7sjx.css';
import '../../css/g/gpq-8xbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq95s7sjx"/><path class="gpq-8xbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:shopping-bag-duty-free" {...props}></Icon>
