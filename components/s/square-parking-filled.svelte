<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb3rc9oyk.css';
import '../../css/g/glve-ra-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb3rc9oyk"/><path clip-rule="evenodd" class="glve-ra-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-parking-filled" {...props}></Icon>
