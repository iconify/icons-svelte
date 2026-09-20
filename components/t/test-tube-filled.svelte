<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqfftaccz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rqfftaccz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:test-tube-filled" {...props}></Icon>
