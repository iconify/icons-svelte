<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn2t-zwkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kn2t-zwkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:sad" {...props}></Icon>
