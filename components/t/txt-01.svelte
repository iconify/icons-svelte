<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_ohfvbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_ohfvbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:txt-01" {...props}></Icon>
