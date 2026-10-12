<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sye9drcvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sye9drcvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-phonetic" {...props}></Icon>
