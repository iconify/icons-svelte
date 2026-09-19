<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6q2q6bbg.css';
import '../../css/n/nkmmv-b0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6q2q6bbg"/><path class="nkmmv-b0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:volume-2-filled" {...props}></Icon>
