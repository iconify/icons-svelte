<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtb9wxb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtb9wxb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:seedlings-solid" {...props}></Icon>
