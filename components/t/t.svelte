<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbc_8fbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sbc_8fbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:t" {...props}></Icon>
