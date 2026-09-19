<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2951jfnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2951jfnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tesla-defrost" {...props}></Icon>
