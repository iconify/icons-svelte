<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei66cbbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei66cbbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:text-aa" {...props}></Icon>
