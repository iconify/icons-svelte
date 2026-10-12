<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff3gqsu_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff3gqsu_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shovel-filled" {...props}></Icon>
