<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf7uh1sir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf7uh1sir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:sea-and-sun" {...props}></Icon>
