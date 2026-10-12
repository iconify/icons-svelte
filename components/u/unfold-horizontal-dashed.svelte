<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbu1mdbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbu1mdbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:unfold-horizontal-dashed" {...props}></Icon>
