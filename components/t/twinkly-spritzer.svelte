<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrobvobrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrobvobrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:twinkly-spritzer" {...props}></Icon>
