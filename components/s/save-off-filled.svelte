<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbltlh2de.css';
import '../../css/f/f0xl0fb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qbltlh2de"/><path class="f0xl0fb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:save-off-filled" {...props}></Icon>
