<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjfvhn6ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zjfvhn6ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-user-round-filled" {...props}></Icon>
