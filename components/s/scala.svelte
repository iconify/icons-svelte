<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md7chzk7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="md7chzk7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:scala" {...props}></Icon>
