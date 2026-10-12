<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx34k9ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bx34k9ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-path" {...props}></Icon>
