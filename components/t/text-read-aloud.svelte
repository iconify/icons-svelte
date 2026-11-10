<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-f5n_baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-f5n_baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-read-aloud" {...props}></Icon>
