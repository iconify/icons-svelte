<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt0vcpc-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt0vcpc-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:sun-horizon" {...props}></Icon>
