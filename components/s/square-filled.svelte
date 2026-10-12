<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_07l1bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_07l1bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-filled" {...props}></Icon>
