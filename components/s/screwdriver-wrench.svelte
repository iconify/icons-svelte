<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwald2b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwald2b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:screwdriver-wrench" {...props}></Icon>
