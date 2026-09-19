<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/e/e-6oifs0n.css';
import '../../css/z/z4jms49hf.css';
import '../../css/i/i-8dbccqw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG2D5J8dbD"><g class="ufeehvblu"><path class="e-6oifs0n"/><path class="z4jms49hf"/><path class="i-8dbccqw"/></g></mask></defs><path mask="url(#SVG2D5J8dbD)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:search" {...props}></Icon>
