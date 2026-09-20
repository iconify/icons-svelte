<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxn06lbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxn06lbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:wondershare-filmora" {...props}></Icon>
