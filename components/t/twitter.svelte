<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nki745thx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nki745thx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:twitter" {...props}></Icon>
