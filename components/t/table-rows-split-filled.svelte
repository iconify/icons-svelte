<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koz_5vb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="koz_5vb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:table-rows-split-filled" {...props}></Icon>
