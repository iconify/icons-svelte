<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahkp4zb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ahkp4zb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:train-small" {...props}></Icon>
