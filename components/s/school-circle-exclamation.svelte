<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8p1x2bhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="h8p1x2bhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:school-circle-exclamation" {...props}></Icon>
