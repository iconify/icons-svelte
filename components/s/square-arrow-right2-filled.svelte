<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4-z_mbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l4-z_mbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-arrow-right2-filled" {...props}></Icon>
