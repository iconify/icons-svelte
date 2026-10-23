<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piwsv7bod.css';
import '../../css/c/c5at6trmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="piwsv7bod"/><path class="c5at6trmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:smartphone-user-round-filled" {...props}></Icon>
