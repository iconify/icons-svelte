<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmw12wbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="bmw12wbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:sad-cry" {...props}></Icon>
