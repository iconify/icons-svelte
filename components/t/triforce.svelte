<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im577vr3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im577vr3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:triforce" {...props}></Icon>
