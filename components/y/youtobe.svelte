<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/a/awoqex7gd.css';
import '../../css/j/jpajjdo8n.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGiSszmc2E"><g class="s9cl3zbei"><path class="awoqex7gd"/><path class="jpajjdo8n"/></g></mask></defs><path mask="url(#SVGiSszmc2E)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:youtobe" {...props}></Icon>
