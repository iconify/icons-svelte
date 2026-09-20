<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxjk6z-uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxjk6z-uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:sun-set-2" {...props}></Icon>
