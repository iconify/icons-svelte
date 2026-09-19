<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqc2czb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqc2czb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:upload-02" {...props}></Icon>
