<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1gvs0ovj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1gvs0ovj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:send-horizontal-filled" {...props}></Icon>
