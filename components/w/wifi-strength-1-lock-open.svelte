<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eafz5sbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eafz5sbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-1-lock-open" {...props}></Icon>
