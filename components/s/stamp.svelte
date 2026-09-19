<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw_58wbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw_58wbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:stamp" {...props}></Icon>
