<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np6b41bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np6b41bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:xmark" {...props}></Icon>
