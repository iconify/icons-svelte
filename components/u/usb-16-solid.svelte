<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq_n1sbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lq_n1sbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:usb-16-solid" {...props}></Icon>
