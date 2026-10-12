<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxur79b5t.css';
import '../../css/y/y95_zrbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxur79b5t"/><path class="y95_zrbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sparkles-filled" {...props}></Icon>
