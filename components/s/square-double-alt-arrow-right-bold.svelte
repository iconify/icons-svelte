<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuywxjb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zuywxjb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-double-alt-arrow-right-bold" {...props}></Icon>
