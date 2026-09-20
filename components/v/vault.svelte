<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc0a1acff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gc0a1acff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vault" {...props}></Icon>
