<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d11_ivbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d11_ivbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:step-back" {...props}></Icon>
