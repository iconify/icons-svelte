<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzmi_8kui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gzmi_8kui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-profile" {...props}></Icon>
