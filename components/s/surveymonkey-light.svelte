<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvg_58ill.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mvg_58ill"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:surveymonkey-light" {...props}></Icon>
