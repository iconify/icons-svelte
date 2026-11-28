<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poupq6bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="poupq6bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:snapchat-solid" {...props}></Icon>
