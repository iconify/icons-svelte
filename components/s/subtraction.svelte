<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sno168bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":14};
const content = `<path class="sno168bul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:subtraction" {...props}></Icon>
