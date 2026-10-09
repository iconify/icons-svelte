<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha3x0fenn.css';
import '../../css/g/ge-9v90ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ha3x0fenn"/><path class="ge-9v90ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermal-store-20" {...props}></Icon>
