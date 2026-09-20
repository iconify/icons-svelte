<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqa6zxbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yqa6zxbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:soundcloud-logo-solid" {...props}></Icon>
