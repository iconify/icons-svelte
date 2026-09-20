<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg00ribqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wg00ribqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vector-bezier-fill" {...props}></Icon>
