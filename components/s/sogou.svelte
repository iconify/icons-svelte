<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz9f6kbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz9f6kbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sogou" {...props}></Icon>
