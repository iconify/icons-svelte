<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/p/pjw4h4wuo.css';
import '../../css/r/rt1h_-mxc.css';
import '../../css/h/hsxkkdbde.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAVOXMIBC"><g class="ufeehvblu"><path class="pjw4h4wuo"/><path class="rt1h_-mxc"/><path class="hsxkkdbde"/></g></mask></defs><path mask="url(#SVGAVOXMIBC)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:shake" {...props}></Icon>
