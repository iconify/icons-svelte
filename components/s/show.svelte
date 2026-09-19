<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spb-dpbsw.css';
import '../../css/i/ilmvj-v8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spb-dpbsw"/><path class="ilmvj-v8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:show" {...props}></Icon>
