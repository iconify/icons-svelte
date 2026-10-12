<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voz3i-6tt.css';
import '../../css/q/q2snesbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voz3i-6tt"/><path class="q2snesbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-sparkles-filled" {...props}></Icon>
