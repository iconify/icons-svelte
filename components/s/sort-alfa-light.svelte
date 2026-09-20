<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jypyrtbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jypyrtbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:sort-alfa-light" {...props}></Icon>
