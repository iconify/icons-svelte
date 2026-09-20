<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g418ypbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g418ypbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tag-text" {...props}></Icon>
