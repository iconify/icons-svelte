<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8al9ob1t.css';
import '../../css/u/us-05tkac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n8al9ob1t"/><path class="us-05tkac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ruler-48-bold" {...props}></Icon>
