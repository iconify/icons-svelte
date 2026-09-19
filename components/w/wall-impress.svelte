<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwcrkhbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwcrkhbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-impress" {...props}></Icon>
