<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f07p2fb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f07p2fb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:surrealdb" {...props}></Icon>
