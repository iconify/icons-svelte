<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1567mgil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1567mgil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-round-pen-filled" {...props}></Icon>
