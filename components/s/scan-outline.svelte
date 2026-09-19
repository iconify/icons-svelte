<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiel8l84e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tiel8l84e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:scan-outline" {...props}></Icon>
