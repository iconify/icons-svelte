<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfgs5d_bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfgs5d_bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:service-fill" {...props}></Icon>
