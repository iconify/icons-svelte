<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae0x7dbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae0x7dbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:sound-wave-off" {...props}></Icon>
