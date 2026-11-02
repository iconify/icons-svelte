<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scszbka3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scszbka3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sidebar-right-open-fill" {...props}></Icon>
