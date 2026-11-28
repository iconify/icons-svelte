<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioaegdccd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ioaegdccd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:square-6" {...props}></Icon>
