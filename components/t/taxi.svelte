<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d_-y1_b1i.css';
import '../../css/e/e501nzbcj.css';
import '../../css/s/s_-e5vbjx.css';
import '../../css/w/w47nbs-tr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG0qIygdYT"><g class="ft5dv1b6b"><path class="d_-y1_b1i"/><path class="e501nzbcj"/><path clip-rule="evenodd" class="s_-e5vbjx"/><path class="w47nbs-tr"/></g></mask></defs><path mask="url(#SVG0qIygdYT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:taxi" {...props}></Icon>
