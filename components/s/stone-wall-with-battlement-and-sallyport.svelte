<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbp3s3hkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lbp3s3hkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:stone-wall-with-battlement-and-sallyport" {...props}></Icon>
