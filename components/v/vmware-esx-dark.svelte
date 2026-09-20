<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgeiyibhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zgeiyibhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vmware-esx-dark" {...props}></Icon>
