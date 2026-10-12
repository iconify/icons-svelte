<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1-vf5x4j.css';
import '../../css/m/mzcm9qfhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d1-vf5x4j"/><path class="mzcm9qfhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:wand-sparkles-filled" {...props}></Icon>
