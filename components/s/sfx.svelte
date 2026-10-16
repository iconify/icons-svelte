<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy_t__bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy_t__bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:sfx" {...props}></Icon>
