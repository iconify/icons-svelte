<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx7jcpb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx7jcpb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-half-solid" {...props}></Icon>
