<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kchgrccaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kchgrccaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:speed-alt-light" {...props}></Icon>
