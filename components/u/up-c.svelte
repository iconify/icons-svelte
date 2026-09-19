<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/o/okuvfmhmk.css';
import '../../css/t/tvgauyb5v.css';
import '../../css/s/secmbabyc.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGREtFiUFR"><g class="s9cl3zbei"><path clip-rule="evenodd" class="okuvfmhmk"/><path class="tvgauyb5v"/><path class="secmbabyc"/></g></mask></defs><path mask="url(#SVGREtFiUFR)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:up-c" {...props}></Icon>
