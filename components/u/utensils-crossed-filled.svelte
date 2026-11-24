<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amxt-xpqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amxt-xpqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:utensils-crossed-filled" {...props}></Icon>
