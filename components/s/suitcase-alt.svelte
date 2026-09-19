<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgirl4yno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":19,"height":24};
const content = `<path class="mgirl4yno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:suitcase-alt" {...props}></Icon>
