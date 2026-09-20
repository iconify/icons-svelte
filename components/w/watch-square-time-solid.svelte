<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aglw7i7ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aglw7i7ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:watch-square-time-solid" {...props}></Icon>
