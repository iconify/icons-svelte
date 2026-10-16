<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7ggesbml.css';
import '../../css/b/by_x3ac6t.css';
import '../../css/s/saqzqrcve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n7ggesbml"/><path class="by_x3ac6t"/><path class="saqzqrcve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:steam-reformer-20-bold" {...props}></Icon>
