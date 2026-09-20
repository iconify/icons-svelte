<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9ppn8jnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h9ppn8jnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:test-tube-minimalistic-outline" {...props}></Icon>
