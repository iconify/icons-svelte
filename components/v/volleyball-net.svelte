<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpuckabpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpuckabpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:volleyball-net" {...props}></Icon>
