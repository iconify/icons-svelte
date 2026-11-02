<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1o8-rjdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1o8-rjdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:unhappy-line" {...props}></Icon>
