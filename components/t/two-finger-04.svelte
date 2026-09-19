<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okig0vbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okig0vbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:two-finger-04" {...props}></Icon>
