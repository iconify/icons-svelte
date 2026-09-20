<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti7rv8b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ti7rv8b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:sculpture" {...props}></Icon>
