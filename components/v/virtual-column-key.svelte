<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl7jbz5fr.css';
import '../../css/h/h_3i35b7d.css';
import '../../css/y/y-dj3mnsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="gl7jbz5fr"/><path class="h_3i35b7d"/><path class="y-dj3mnsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:virtual-column-key" {...props}></Icon>
