<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oslr7smei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oslr7smei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:thumbs-down-filled" {...props}></Icon>
