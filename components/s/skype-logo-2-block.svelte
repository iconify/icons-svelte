<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm0f2cccm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lm0f2cccm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:skype-logo-2-block" {...props}></Icon>
