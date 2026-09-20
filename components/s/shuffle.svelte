<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-ftrm2ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-ftrm2ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:shuffle" {...props}></Icon>
