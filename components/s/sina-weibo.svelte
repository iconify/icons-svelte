<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r04k3wdfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r04k3wdfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:sina-weibo" {...props}></Icon>
