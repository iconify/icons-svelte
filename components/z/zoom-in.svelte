<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/e/e-6oifs0n.css';
import '../../css/r/r395l6xbw.css';
import '../../css/i/i-8dbccqw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4kTyDeBb"><g class="ufeehvblu"><path class="e-6oifs0n"/><path class="r395l6xbw"/><path class="i-8dbccqw"/></g></mask></defs><path mask="url(#SVG4kTyDeBb)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:zoom-in" {...props}></Icon>
