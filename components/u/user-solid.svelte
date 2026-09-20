<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgmkf8j1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgmkf8j1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:user-solid" {...props}></Icon>
