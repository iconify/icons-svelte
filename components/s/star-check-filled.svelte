<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2lhz8f1q.css';
import '../../css/v/vnjnmccnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2lhz8f1q"/><path class="vnjnmccnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:star-check-filled" {...props}></Icon>
