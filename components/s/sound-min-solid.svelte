<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvy1shbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zvy1shbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:sound-min-solid" {...props}></Icon>
