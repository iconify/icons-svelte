<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsy6m-bng.css';
import '../../css/j/j04z_-bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hsy6m-bng"/><path class="j04z_-bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:undo-20" {...props}></Icon>
