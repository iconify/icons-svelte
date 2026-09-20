<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk1sc4blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk1sc4blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wifi-medium" {...props}></Icon>
