<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyvfaw90f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyvfaw90f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:table-remove" {...props}></Icon>
