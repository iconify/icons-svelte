<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl8qmubzh.css';
import '../../css/q/qwd-pmblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl8qmubzh"/><path class="qwd-pmblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-vertical-bold-duotone" {...props}></Icon>
