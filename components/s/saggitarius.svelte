<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqfm60b_p.css';
import '../../css/h/hrtye35bf.css';
import '../../css/b/b3p0cjlsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qqfm60b_p"/><path class="hrtye35bf"/><path class="b3p0cjlsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:saggitarius" {...props}></Icon>
