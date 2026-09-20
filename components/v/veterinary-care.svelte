<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhcm9w7gk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="xhcm9w7gk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:veterinary-care" {...props}></Icon>
