<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srezkwbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="srezkwbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:work-item-task" {...props}></Icon>
