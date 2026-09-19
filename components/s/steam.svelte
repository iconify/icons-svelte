<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkxco0b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkxco0b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:steam" {...props}></Icon>
