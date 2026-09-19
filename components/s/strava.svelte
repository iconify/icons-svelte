<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/het-occyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="het-occyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:strava" {...props}></Icon>
