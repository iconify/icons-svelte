<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8lnf7b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l8lnf7b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:surrealdb" {...props}></Icon>
