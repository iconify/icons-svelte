<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbf1i-a_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbf1i-a_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:transition-top-filled" {...props}></Icon>
