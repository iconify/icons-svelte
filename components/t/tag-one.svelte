<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ijmm-rb2y.css';
import '../../css/s/s9x15swgn.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxewEkxmK"><g class="ft5dv1b6b"><path class="ijmm-rb2y"/><path clip-rule="evenodd" class="s9x15swgn"/></g></mask></defs><path mask="url(#SVGxewEkxmK)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:tag-one" {...props}></Icon>
