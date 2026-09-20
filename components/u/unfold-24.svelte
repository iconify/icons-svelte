<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnghg2bjh.css';
import '../../css/f/f7ef8jq2f.css';
import '../../css/x/xtctq8bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnghg2bjh"/><path class="f7ef8jq2f"/><path class="xtctq8bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:unfold-24" {...props}></Icon>
