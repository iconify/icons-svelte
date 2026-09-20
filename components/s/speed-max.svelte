<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3en-iwpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m3en-iwpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:speed-max" {...props}></Icon>
