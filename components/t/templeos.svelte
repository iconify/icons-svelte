<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odpzhpb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":473,"height":512};
const content = `<path class="odpzhpb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:templeos" {...props}></Icon>
