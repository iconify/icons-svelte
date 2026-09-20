<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyjird44w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyjird44w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:routing-filled" {...props}></Icon>
