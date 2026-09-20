<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu2b1hbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu2b1hbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:shopping-bag" {...props}></Icon>
