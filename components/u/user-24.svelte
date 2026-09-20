<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r86igdcpy.css';
import '../../css/z/zqwnycjqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r86igdcpy"/><path clip-rule="evenodd" class="zqwnycjqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:user-24" {...props}></Icon>
