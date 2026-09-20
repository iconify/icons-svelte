<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er2a5vi2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er2a5vi2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:trending-solid" {...props}></Icon>
