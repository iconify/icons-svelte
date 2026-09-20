<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyv23pb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qyv23pb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:vertex" {...props}></Icon>
