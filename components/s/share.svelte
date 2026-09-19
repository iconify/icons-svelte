<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itak21rgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="itak21rgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:share" {...props}></Icon>
