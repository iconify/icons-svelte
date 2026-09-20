<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jid4_bb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="jid4_bb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:warning-diamond" {...props}></Icon>
