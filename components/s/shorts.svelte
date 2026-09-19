<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/phem8ng6e.css';
import '../../css/p/pg706ac6b.css';
import '../../css/q/q46dpkbew.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6qgA8cHB"><g class="ft5dv1b6b"><path class="phem8ng6e"/><path class="pg706ac6b"/><path class="q46dpkbew"/></g></mask></defs><path mask="url(#SVG6qgA8cHB)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:shorts" {...props}></Icon>
