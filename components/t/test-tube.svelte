<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svnjfrbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svnjfrbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:test-tube" {...props}></Icon>
