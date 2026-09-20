<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkul0jf2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="dkul0jf2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:trophy" {...props}></Icon>
