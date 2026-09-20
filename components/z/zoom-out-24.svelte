<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4_lrfb5n.css';
import '../../css/s/scnvldbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4_lrfb5n"/><path class="scnvldbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:zoom-out-24" {...props}></Icon>
