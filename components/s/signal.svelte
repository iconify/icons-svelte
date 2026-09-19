<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au6ph-b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="au6ph-b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:signal" {...props}></Icon>
