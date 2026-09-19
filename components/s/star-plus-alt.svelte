<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moa8elbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moa8elbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:star-plus-alt" {...props}></Icon>
