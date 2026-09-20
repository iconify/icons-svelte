<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v607facly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v607facly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:upload-expressive" {...props}></Icon>
