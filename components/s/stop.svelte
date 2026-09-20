<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtp7n9szp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtp7n9szp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:stop" {...props}></Icon>
