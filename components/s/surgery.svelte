<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrgssux7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="zrgssux7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:surgery" {...props}></Icon>
