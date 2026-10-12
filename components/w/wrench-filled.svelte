<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eak51fbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eak51fbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:wrench-filled" {...props}></Icon>
