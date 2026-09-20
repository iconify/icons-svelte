<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qervw3b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qervw3b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:transfer-long-top-light" {...props}></Icon>
