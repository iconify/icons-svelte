<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhqbrmbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhqbrmbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:wallet" {...props}></Icon>
