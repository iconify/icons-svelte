<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6q2q6bbg.css';
import '../../css/u/ut_zgf51k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6q2q6bbg"/><path class="ut_zgf51k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:volume-max-filled" {...props}></Icon>
