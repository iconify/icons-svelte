<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isbvslb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="isbvslb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:stan" {...props}></Icon>
