<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/ol2q0bijy.css';
import '../../css/j/j2n4kybwy.css';
import '../../css/e/ejxs69auf.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG0otHQdzY"><g class="ufeehvblu"><rect class="ol2q0bijy"/><path class="j2n4kybwy"/><path class="ejxs69auf"/></g></mask></defs><path mask="url(#SVG0otHQdzY)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:unlock" {...props}></Icon>
