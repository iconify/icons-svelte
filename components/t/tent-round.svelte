<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1odkg-wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1odkg-wd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tent-round" {...props}></Icon>
