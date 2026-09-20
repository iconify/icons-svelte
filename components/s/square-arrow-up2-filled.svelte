<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyyr3w7qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uyyr3w7qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-arrow-up2-filled" {...props}></Icon>
