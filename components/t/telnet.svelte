<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yombd9vlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yombd9vlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:telnet" {...props}></Icon>
