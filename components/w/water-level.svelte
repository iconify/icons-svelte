<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/p/pr0r_23gm.css';
import '../../css/g/g1j_4nbjv.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGuIAk4cPA"><g class="v3_i3wktz"><path clip-rule="evenodd" class="pr0r_23gm"/><path class="g1j_4nbjv"/></g></mask></defs><path mask="url(#SVGuIAk4cPA)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:water-level" {...props}></Icon>
