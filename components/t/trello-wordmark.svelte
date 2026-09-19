<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw2o4bb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bw2o4bb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:trello-wordmark" {...props}></Icon>
