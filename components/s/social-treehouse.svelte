<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae7h3dvvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ae7h3dvvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-treehouse" {...props}></Icon>
