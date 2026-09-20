<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5ckzvuqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y5ckzvuqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:trumpet-16" {...props}></Icon>
