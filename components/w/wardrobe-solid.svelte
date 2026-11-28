<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezcgh90ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezcgh90ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wardrobe-solid" {...props}></Icon>
