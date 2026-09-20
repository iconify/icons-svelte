<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyt5i2b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyt5i2b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:upload-cloud-line" {...props}></Icon>
