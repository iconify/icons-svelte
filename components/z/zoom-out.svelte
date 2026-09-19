<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/e/e-6oifs0n.css';
import '../../css/j/jvput-vek.css';
import '../../css/i/i-8dbccqw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGrYzOtcUx"><g class="ufeehvblu"><path class="e-6oifs0n"/><path class="jvput-vek"/><path class="i-8dbccqw"/></g></mask></defs><path mask="url(#SVGrYzOtcUx)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:zoom-out" {...props}></Icon>
