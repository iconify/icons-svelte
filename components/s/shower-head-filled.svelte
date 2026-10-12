<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owfrw6bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owfrw6bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shower-head-filled" {...props}></Icon>
