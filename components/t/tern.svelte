<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnlx58bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":491,"height":512};
const content = `<path class="hnlx58bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:tern" {...props}></Icon>
