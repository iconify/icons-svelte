<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh-63tbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dh-63tbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wordpress" {...props}></Icon>
