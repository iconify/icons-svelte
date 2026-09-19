<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5b4yxk4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5b4yxk4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:sparkles" {...props}></Icon>
