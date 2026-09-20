<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl8db2yaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl8db2yaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:signa" {...props}></Icon>
