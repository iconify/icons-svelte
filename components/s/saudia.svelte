<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt-wwvyfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt-wwvyfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:saudia" {...props}></Icon>
