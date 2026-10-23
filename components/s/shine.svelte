<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyngsypel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyngsypel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:shine" {...props}></Icon>
