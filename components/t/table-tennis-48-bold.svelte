<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezsp4f-sb.css';
import '../../css/w/w24yo_x-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ezsp4f-sb"/><path class="w24yo_x-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:table-tennis-48-bold" {...props}></Icon>
