<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7q_wsbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w7q_wsbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shield-2-solid" {...props}></Icon>
