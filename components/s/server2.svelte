<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq5e5r7xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nq5e5r7xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:server2" {...props}></Icon>
