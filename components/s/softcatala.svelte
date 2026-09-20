<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghd_tacsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghd_tacsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:softcatala" {...props}></Icon>
