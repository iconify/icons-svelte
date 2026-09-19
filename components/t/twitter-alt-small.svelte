<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlsk20ghj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jlsk20ghj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:twitter-alt-small" {...props}></Icon>
