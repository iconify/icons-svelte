<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnvyml-_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnvyml-_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vip-2-line" {...props}></Icon>
