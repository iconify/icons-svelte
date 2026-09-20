<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcw1c79qb.css';
import '../../css/b/beeg7e7hg.css';
import '../../css/f/fv-cmacjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcw1c79qb"/><path class="beeg7e7hg"/><path class="fv-cmacjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:save-filled" {...props}></Icon>
