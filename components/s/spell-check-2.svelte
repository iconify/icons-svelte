<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqpax39ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqpax39ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:spell-check-2" {...props}></Icon>
