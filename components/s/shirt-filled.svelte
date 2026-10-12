<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug5nw9bdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug5nw9bdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shirt-filled" {...props}></Icon>
