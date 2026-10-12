<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxq908p6m.css';
import '../../css/m/mdkytublt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxq908p6m"/><path class="mdkytublt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:traffic-cone-filled" {...props}></Icon>
