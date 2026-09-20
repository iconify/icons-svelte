<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjd0hm9at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjd0hm9at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-slash" {...props}></Icon>
