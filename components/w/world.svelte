<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckny4dw-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckny4dw-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:world" {...props}></Icon>
