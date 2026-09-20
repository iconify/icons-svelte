<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp-srlbgu.css';
import '../../css/w/w2xbvabvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bp-srlbgu"/><path class="w2xbvabvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:usulnet" {...props}></Icon>
