<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3-5554gl.css';
import '../../css/l/lmgxn5bcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3-5554gl"/><path class="lmgxn5bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:x-circle" {...props}></Icon>
