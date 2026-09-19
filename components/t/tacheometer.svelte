<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/annezhqqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="annezhqqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:tacheometer" {...props}></Icon>
