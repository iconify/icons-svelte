<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6a9xhbrm.css';
import '../../css/x/x8n4ul95g.css';
import '../../css/k/ksc_xx8rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f6a9xhbrm"/><path class="x8n4ul95g"/><path class="ksc_xx8rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:safe-48-bold" {...props}></Icon>
