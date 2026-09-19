<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/carmii-dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="carmii-dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:share" {...props}></Icon>
