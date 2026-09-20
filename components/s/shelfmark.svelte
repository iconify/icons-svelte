<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj8_-65to.css';
import '../../css/t/tig70s96w.css';
import '../../css/c/cf2gljolc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="xj8_-65to"/><path class="tig70s96w"/><path class="cf2gljolc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shelfmark" {...props}></Icon>
