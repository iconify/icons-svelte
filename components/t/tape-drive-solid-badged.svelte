<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpykv1bud.css';
import '../../css/o/o760gtbbr.css';
import '../../css/l/lmf0ecbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="rpykv1bud"/><path class="o760gtbbr"/><circle class="lmf0ecbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:tape-drive-solid-badged" {...props}></Icon>
