<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9-2m5u6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r9-2m5u6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:view-month" {...props}></Icon>
