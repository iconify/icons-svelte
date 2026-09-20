<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssk1sbbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ssk1sbbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:save-as-filled" {...props}></Icon>
