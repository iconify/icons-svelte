<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dht2r7dts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dht2r7dts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ty" {...props}></Icon>
