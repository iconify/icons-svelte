<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx7s3ezkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx7s3ezkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:zoom-in-fill" {...props}></Icon>
