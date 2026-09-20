<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_jv0bcna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_jv0bcna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user4-filled" {...props}></Icon>
