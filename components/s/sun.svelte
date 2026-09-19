<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh-b04byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kh-b04byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:sun" {...props}></Icon>
