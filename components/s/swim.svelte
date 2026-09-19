<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_9wi13wp.css';
import '../../css/j/jinb2jzjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="l_9wi13wp"/><path class="jinb2jzjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:swim" {...props}></Icon>
