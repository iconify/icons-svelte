<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynyb3aclq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynyb3aclq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-letter-t-filled" {...props}></Icon>
