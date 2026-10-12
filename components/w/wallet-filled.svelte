<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf4murbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lf4murbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:wallet-filled" {...props}></Icon>
