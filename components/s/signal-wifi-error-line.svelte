<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymesejb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymesejb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signal-wifi-error-line" {...props}></Icon>
