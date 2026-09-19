<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4bk81bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m4bk81bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:z-systems" {...props}></Icon>
