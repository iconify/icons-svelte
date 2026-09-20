<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxmw32r0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxmw32r0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:vector-intersection" {...props}></Icon>
