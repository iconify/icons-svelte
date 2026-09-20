<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv62uor1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vv62uor1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:sign-in-alt-line" {...props}></Icon>
