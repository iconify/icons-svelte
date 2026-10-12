<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxxa1hb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lxxa1hb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:skull-filled" {...props}></Icon>
