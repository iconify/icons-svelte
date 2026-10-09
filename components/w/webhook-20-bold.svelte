<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki204cc1a.css';
import '../../css/x/xe7g4rbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ki204cc1a"/><path class="xe7g4rbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:webhook-20-bold" {...props}></Icon>
