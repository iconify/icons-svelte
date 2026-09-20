<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po468yrgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="po468yrgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shield-x" {...props}></Icon>
