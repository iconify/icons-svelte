<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku1p59bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku1p59bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-indent-less" {...props}></Icon>
