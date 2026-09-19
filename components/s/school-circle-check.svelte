<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1-7jrbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="z1-7jrbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:school-circle-check" {...props}></Icon>
