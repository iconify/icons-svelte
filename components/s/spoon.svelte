<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0b-z2s3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1792};
const content = `<path class="o0b-z2s3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:spoon" {...props}></Icon>
