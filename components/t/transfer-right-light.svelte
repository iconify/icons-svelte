<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am88q0t7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am88q0t7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:transfer-right-light" {...props}></Icon>
