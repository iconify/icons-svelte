<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s__vy8qom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s__vy8qom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:washer2" {...props}></Icon>
