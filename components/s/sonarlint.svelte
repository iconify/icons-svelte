<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnd6hlbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnd6hlbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sonarlint" {...props}></Icon>
