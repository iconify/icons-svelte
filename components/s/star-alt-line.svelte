<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9cgcjmqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9cgcjmqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:star-alt-line" {...props}></Icon>
