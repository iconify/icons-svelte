<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntr9l2cws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ntr9l2cws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tcp-ip-service" {...props}></Icon>
