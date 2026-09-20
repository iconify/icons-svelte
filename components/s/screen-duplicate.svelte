<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5lfbgmeg.css';
import '../../css/c/cqafvmdbv.css';
import '../../css/w/whsz71boo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b5lfbgmeg"/><path class="cqafvmdbv"/><path clip-rule="evenodd" class="whsz71boo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:screen-duplicate" {...props}></Icon>
