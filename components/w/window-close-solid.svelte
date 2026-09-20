<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3lnfob0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3lnfob0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:window-close-solid" {...props}></Icon>
