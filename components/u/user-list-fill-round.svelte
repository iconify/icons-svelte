<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfjgrpbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfjgrpbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-list-fill-round" {...props}></Icon>
