<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqv7gzxhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqv7gzxhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sydney-metro" {...props}></Icon>
