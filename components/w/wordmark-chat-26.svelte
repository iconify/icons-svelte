<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_ysxsbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":47,"height":26};
const content = `<path class="h_ysxsbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wordmark-chat-26" {...props}></Icon>
