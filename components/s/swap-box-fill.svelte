<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2ntsjsbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2ntsjsbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:swap-box-fill" {...props}></Icon>
