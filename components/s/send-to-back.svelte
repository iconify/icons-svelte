<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/o/o76v0vh3i.css';
import '../../css/x/xdmoomhwk.css';
import '../../css/j/jc6ju62gl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVHGVby4n"><g class="v3_i3wktz"><path class="o76v0vh3i"/><path class="xdmoomhwk"/><path class="jc6ju62gl"/></g></mask></defs><path mask="url(#SVGVHGVby4n)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:send-to-back" {...props}></Icon>
