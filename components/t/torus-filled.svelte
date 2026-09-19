<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laalgyble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="laalgyble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:torus-filled" {...props}></Icon>
