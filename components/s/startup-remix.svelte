<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aezuf9byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aezuf9byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:startup-remix" {...props}></Icon>
