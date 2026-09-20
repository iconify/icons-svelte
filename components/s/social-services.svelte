<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr_0ps4dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="pr_0ps4dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:social-services" {...props}></Icon>
