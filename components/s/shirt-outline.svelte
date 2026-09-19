<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exs91hbwo.css';
import '../../css/k/kxpsf4byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="exs91hbwo"/><path class="kxpsf4byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:shirt-outline" {...props}></Icon>
