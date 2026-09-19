<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/l/lvwaq0byj.css';
import '../../css/o/opbtt0byp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzSbqXbqj"><g class="ufeehvblu"><path class="lvwaq0byj"/><path class="opbtt0byp"/></g></mask></defs><path mask="url(#SVGzSbqXbqj)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:shield-add" {...props}></Icon>
