<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr9k79o_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr9k79o_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wifi-no-signal" {...props}></Icon>
