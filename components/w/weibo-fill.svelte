<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb-m5b01n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb-m5b01n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:weibo-fill" {...props}></Icon>
