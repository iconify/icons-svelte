<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qusu2jbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qusu2jbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tank-line" {...props}></Icon>
