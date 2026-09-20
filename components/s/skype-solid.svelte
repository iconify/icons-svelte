<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym_l82hyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ym_l82hyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:skype-solid" {...props}></Icon>
