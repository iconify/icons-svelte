<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k3mn7piaq.css';
import '../../css/k/kz8euhb7z.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGuw5dzeYm"><g class="ft5dv1b6b"><path class="k3mn7piaq"/><path clip-rule="evenodd" class="kz8euhb7z"/></g></mask></defs><path mask="url(#SVGuw5dzeYm)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:tag-one" {...props}></Icon>
