<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m41qtkyur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m41qtkyur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:sanitizer" {...props}></Icon>
