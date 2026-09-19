<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lksygobov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lksygobov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:storm-tracker" {...props}></Icon>
