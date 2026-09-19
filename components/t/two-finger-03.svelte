<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkv49fbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkv49fbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:two-finger-03" {...props}></Icon>
