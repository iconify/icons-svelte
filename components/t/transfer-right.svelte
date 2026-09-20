<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2-y6acjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2-y6acjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:transfer-right" {...props}></Icon>
