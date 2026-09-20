<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2a1q1bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2a1q1bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:steem" {...props}></Icon>
