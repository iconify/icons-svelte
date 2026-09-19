<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzcs35b4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzcs35b4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:two-finger-05" {...props}></Icon>
