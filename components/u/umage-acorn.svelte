<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-i24ccuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-i24ccuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:umage-acorn" {...props}></Icon>
