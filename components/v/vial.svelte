<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_o9ybcwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_o9ybcwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:vial" {...props}></Icon>
