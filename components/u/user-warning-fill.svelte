<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnrsrt4wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnrsrt4wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-warning-fill" {...props}></Icon>
