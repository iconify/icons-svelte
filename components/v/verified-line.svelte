<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrnix4hzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrnix4hzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:verified-line" {...props}></Icon>
