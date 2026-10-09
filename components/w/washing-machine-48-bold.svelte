<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9c993b2t.css';
import '../../css/y/yu6hplrgd.css';
import '../../css/k/kauhwtbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x9c993b2t"/><path class="yu6hplrgd"/><path class="kauhwtbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:washing-machine-48-bold" {...props}></Icon>
