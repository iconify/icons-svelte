<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqehv-afi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jqehv-afi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:ruler-2" {...props}></Icon>
