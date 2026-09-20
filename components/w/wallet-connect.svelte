<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5_8e0yrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5_8e0yrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wallet-connect" {...props}></Icon>
