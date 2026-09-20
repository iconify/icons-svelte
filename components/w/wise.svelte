<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsrignk3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsrignk3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:wise" {...props}></Icon>
