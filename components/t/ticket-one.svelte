<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/m/mkcveibug.css';
import '../../css/z/zzqn8_sjh.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGz1QUNeza"><g class="hv130ab-t"><path class="mkcveibug"/><path class="zzqn8_sjh"/></g></mask></defs><path mask="url(#SVGz1QUNeza)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:ticket-one" {...props}></Icon>
