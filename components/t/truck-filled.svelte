<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_od4ab8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_od4ab8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:truck-filled" {...props}></Icon>
