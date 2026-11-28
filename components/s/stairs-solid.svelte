<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwv2r1bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwv2r1bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:stairs-solid" {...props}></Icon>
