<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvu2yvxqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvu2yvxqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:twinkly-icicle" {...props}></Icon>
