<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow1beibmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ow1beibmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-multiple-circle-solid" {...props}></Icon>
