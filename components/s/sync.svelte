<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmc3rgxgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmc3rgxgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sync" {...props}></Icon>
