<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi_sn268h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi_sn268h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:space-key" {...props}></Icon>
