<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi8xt8byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi8xt8byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-remove-fill" {...props}></Icon>
