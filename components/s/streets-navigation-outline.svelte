<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1uoukbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x1uoukbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:streets-navigation-outline" {...props}></Icon>
