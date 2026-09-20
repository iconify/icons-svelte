<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io412tbjd.css';
import '../../css/o/oj-_-5bcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="io412tbjd"/><path class="oj-_-5bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:toodoom" {...props}></Icon>
