<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rddng9bnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rddng9bnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:vk-with-circle" {...props}></Icon>
