<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae5jc82yp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ae5jc82yp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-profile" {...props}></Icon>
