<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smhe7gbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smhe7gbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:table-filled" {...props}></Icon>
