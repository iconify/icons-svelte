<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvyijfb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bvyijfb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ticket-x-filled" {...props}></Icon>
