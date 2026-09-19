<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h14yaqw0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="h14yaqw0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:step-backwrad" {...props}></Icon>
