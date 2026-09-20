<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqz67i20m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="zqz67i20m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:tablet-f" {...props}></Icon>
