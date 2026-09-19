<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk6x0-gcj.css';
import '../../css/j/jw9a98ysj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk6x0-gcj"/><path class="jw9a98ysj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:work-os" {...props}></Icon>
