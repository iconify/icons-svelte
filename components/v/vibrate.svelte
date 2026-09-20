<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm1fd75xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pm1fd75xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:vibrate" {...props}></Icon>
