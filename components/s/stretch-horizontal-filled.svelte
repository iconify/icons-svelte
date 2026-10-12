<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kza05hb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kza05hb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:stretch-horizontal-filled" {...props}></Icon>
