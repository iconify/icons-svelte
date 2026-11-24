<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfsld5xui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfsld5xui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:spotlight-filled" {...props}></Icon>
