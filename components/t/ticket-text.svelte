<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sof9ji8mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sof9ji8mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:ticket-text" {...props}></Icon>
