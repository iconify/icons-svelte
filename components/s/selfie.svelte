<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_-njn0sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_-njn0sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:selfie" {...props}></Icon>
