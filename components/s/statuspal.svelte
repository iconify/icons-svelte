<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbryrkb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbryrkb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:statuspal" {...props}></Icon>
