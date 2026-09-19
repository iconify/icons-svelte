<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/z/zsyk_j46v.css';
import '../../css/s/si-nqabns.css';
import '../../css/d/dkfj0ub_t.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlANxqehJ"><g class="hv130ab-t"><path class="zsyk_j46v"/><path class="si-nqabns"/><path class="dkfj0ub_t"/></g></mask></defs><path mask="url(#SVGlANxqehJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:ticket" {...props}></Icon>
