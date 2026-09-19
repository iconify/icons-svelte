<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a98i3bc2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="a98i3bc2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:test-tubes" {...props}></Icon>
