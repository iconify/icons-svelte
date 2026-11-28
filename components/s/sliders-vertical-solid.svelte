<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8ilij-le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8ilij-le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sliders-vertical-solid" {...props}></Icon>
