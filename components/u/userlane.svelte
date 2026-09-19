<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjz-x1bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjz-x1bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:userlane" {...props}></Icon>
