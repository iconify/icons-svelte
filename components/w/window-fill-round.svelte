<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2mq-n2xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2mq-n2xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-fill-round" {...props}></Icon>
