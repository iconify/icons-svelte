<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxib_rb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxib_rb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:trending-down" {...props}></Icon>
