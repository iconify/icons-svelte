<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjkwd0byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjkwd0byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:video-check-fill" {...props}></Icon>
