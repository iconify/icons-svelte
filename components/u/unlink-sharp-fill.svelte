<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvhg3tb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvhg3tb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:unlink-sharp-fill" {...props}></Icon>
