<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajaek5qjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajaek5qjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:smart-watch" {...props}></Icon>
