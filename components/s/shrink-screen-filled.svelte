<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uev-y9bxq.css';
import '../../css/h/hurcj9b3v.css';
import '../../css/v/v758r-tyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<rect class="uev-y9bxq"/><path class="hurcj9b3v"/><path class="v758r-tyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:shrink-screen-filled" {...props}></Icon>
