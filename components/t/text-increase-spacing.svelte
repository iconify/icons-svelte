<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhhhswtjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhhhswtjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-increase-spacing" {...props}></Icon>
