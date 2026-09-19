<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn7w4tbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="bn7w4tbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:user-minus" {...props}></Icon>
