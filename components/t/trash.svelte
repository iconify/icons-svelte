<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjz1nm3be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="qjz1nm3be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:trash" {...props}></Icon>
