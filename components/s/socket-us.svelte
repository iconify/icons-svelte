<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah-cd359b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah-cd359b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:socket-us" {...props}></Icon>
