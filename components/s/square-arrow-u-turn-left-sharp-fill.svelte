<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylib_ubbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ylib_ubbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-u-turn-left-sharp-fill" {...props}></Icon>
