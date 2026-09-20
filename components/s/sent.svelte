<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7vd29bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="r7vd29bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:sent" {...props}></Icon>
