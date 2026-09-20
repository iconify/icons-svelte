<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qstqh6buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qstqh6buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:tickets" {...props}></Icon>
