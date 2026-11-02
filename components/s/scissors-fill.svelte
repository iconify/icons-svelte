<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayln2ubqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayln2ubqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scissors-fill" {...props}></Icon>
