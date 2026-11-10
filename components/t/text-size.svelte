<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czbr_75eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czbr_75eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-size" {...props}></Icon>
