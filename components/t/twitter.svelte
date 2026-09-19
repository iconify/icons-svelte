<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzoe9qb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzoe9qb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:twitter" {...props}></Icon>
