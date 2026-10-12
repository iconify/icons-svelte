<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df92hcbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="df92hcbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:search-slash-filled" {...props}></Icon>
