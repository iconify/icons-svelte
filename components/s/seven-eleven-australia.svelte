<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3j8d_pdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3j8d_pdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:seven-eleven-australia" {...props}></Icon>
