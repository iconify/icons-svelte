<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tua-0ebsr.css';
import '../../css/h/h7kltebkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tua-0ebsr"/><path class="h7kltebkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-arrow-left-exit-filled" {...props}></Icon>
