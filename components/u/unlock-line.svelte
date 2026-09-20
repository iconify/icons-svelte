<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw54qac6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw54qac6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:unlock-line" {...props}></Icon>
