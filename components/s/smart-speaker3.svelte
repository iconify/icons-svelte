<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmqw1zl_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zmqw1zl_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:smart-speaker3" {...props}></Icon>
