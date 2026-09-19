<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrvrercle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrvrercle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:square" {...props}></Icon>
