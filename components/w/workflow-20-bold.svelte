<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg4v4ywuk.css';
import '../../css/g/ghmmfobwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eg4v4ywuk"/><path class="ghmmfobwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:workflow-20-bold" {...props}></Icon>
