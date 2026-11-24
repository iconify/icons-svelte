<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9auu3bne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9auu3bne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sun-snow-filled" {...props}></Icon>
