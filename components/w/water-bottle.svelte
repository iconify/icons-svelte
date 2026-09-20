<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezqm6lbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":48};
const content = `<path class="ezqm6lbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:water-bottle" {...props}></Icon>
