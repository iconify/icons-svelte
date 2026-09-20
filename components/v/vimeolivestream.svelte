<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/curl4d8tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="curl4d8tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:vimeolivestream" {...props}></Icon>
