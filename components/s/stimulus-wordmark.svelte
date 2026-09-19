<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axqjiccfh.css';
import '../../css/n/nuioz00-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="axqjiccfh"/><path class="nuioz00-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:stimulus-wordmark" {...props}></Icon>
