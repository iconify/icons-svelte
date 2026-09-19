<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta51_fbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ta51_fbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:surrealdb-wordmark" {...props}></Icon>
