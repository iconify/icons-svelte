<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm_oih19f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm_oih19f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sun-fill" {...props}></Icon>
