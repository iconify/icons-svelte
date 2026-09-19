<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqwkt9bhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqwkt9bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:starlink" {...props}></Icon>
