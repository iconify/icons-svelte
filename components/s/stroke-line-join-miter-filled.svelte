<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un5g80wwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="un5g80wwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:stroke-line-join-miter-filled" {...props}></Icon>
