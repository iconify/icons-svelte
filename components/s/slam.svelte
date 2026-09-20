<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x61jlibhq.css';
import '../../css/r/r9bbvybua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x61jlibhq"/><path clip-rule="evenodd" class="r9bbvybua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:slam" {...props}></Icon>
