<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezb6zpbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ezb6zpbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:svelte" {...props}></Icon>
