<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpsb-zb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qpsb-zb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:snail-filled" {...props}></Icon>
