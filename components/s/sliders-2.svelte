<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqyjh7hii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqyjh7hii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:sliders-2" {...props}></Icon>
