<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/eebbqibke.css';
import '../../css/i/i7z607m3y.css';
import '../../css/s/s_-e5vbjx.css';
import '../../css/v/vi4-tbc9j.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvE0ncbKk"><g class="ft5dv1b6b"><path class="eebbqibke"/><path class="i7z607m3y"/><path clip-rule="evenodd" class="s_-e5vbjx"/><path class="vi4-tbc9j"/></g></mask></defs><path mask="url(#SVGvE0ncbKk)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:taxi" {...props}></Icon>
