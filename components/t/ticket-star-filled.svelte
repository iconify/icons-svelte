<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_spl1byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_spl1byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ticket-star-filled" {...props}></Icon>
