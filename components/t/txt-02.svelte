<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw3cgebpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aw3cgebpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:txt-02" {...props}></Icon>
