<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpptg2b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qpptg2b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-dot-filled" {...props}></Icon>
