<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2yb-98oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2yb-98oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:send" {...props}></Icon>
