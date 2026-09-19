<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0rcf4lyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0rcf4lyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:square" {...props}></Icon>
