<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lptlgnzoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lptlgnzoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:tan" {...props}></Icon>
