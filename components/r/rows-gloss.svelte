<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so-2c2wtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so-2c2wtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rows-gloss" {...props}></Icon>
