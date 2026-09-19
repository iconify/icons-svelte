<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yad_asbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yad_asbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:send-diagonal-solid" {...props}></Icon>
