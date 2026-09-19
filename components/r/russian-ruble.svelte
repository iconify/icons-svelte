<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfqfntvxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfqfntvxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:russian-ruble" {...props}></Icon>
