<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqxl8rbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sqxl8rbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:speed-alt" {...props}></Icon>
