<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8rgck7vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8rgck7vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shop-line" {...props}></Icon>
