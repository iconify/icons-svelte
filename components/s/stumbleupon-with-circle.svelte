<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqq4x7xuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uqq4x7xuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:stumbleupon-with-circle" {...props}></Icon>
