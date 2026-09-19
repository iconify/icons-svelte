<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyk415qex.css';
import '../../css/s/sokimzycn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyk415qex"/><path class="sokimzycn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:watermelon-filled" {...props}></Icon>
