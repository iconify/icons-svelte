<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-303cb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-303cb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:stethoscope" {...props}></Icon>
