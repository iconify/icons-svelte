<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxr2-_brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qxr2-_brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:x-circle-16-solid" {...props}></Icon>
