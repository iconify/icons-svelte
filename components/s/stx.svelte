<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-_e-ybmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-_e-ybmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:stx" {...props}></Icon>
