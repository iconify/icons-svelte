<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je7ywpbue.css';
import '../../css/v/v02n93nor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="je7ywpbue"/><path class="v02n93nor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trending-up-20-bold" {...props}></Icon>
